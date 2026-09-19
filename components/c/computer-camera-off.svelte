<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bttm99b0u.css';
import '../../css/a/a6m8tsd_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bttm99b0u duoicon-primary-layer"/><path class="a6m8tsd_d duoicon-secondary-layer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:computer-camera-off" {...props}></Icon>
