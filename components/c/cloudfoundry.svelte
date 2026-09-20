<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtdh4fb_d.css';
import '../../css/u/upx6wfzth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rtdh4fb_d"/><path class="upx6wfzth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:cloudfoundry" {...props}></Icon>
