<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/ql38_tbjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":850};
const content = `<path class="ql38_tbjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:flag" {...props}></Icon>
