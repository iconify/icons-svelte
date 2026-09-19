<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck_742b9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2000,"height":2000};
const content = `<path class="ck_742b9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:ad-hoc-marker" {...props}></Icon>
