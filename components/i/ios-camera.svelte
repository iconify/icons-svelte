<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrcd7qbgp.css';
import '../../css/b/b8kj2gpmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="mrcd7qbgp"/><path class="b8kj2gpmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-camera" {...props}></Icon>
