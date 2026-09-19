<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/em_woxjjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="em_woxjjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:doc-text" {...props}></Icon>
