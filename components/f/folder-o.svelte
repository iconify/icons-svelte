<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhc7zgogx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1408};
const content = `<path class="qhc7zgogx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:folder-o" {...props}></Icon>
