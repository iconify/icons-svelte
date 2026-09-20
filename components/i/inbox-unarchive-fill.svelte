<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_8l5ccfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_8l5ccfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:inbox-unarchive-fill" {...props}></Icon>
