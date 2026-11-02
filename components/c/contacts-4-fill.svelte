<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wm_tvin8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm_tvin8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:contacts-4-fill" {...props}></Icon>
