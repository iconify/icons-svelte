<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw_0fyb7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fw_0fyb7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:moon-solid" {...props}></Icon>
