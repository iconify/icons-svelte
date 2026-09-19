<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3c8hybgh.css';
import '../../css/i/izfww2b3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="g3c8hybgh"/><path class="izfww2b3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-camera" {...props}></Icon>
