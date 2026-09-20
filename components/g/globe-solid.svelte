<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4ug5rbfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f4ug5rbfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:globe-solid" {...props}></Icon>
