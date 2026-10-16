<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iu-_06bfk.css';
import '../../css/q/qzu5cgzuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="iu-_06bfk"/><path class="qzu5cgzuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:nodule-48" {...props}></Icon>
