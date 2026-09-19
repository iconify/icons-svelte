<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm6s_5b-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fm6s_5b-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:number-small-3" {...props}></Icon>
