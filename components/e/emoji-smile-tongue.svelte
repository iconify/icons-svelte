<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xineib3hr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xineib3hr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:emoji-smile-tongue" {...props}></Icon>
