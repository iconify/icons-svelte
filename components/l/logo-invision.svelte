<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uaw-qgukg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uaw-qgukg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:logo-invision" {...props}></Icon>
