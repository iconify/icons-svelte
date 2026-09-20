<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwr-9-b4c.css';
import '../../css/z/z2amuho-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iwr-9-b4c"/><path clip-rule="evenodd" class="z2amuho-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:light-bulb-exclamation-duotone" {...props}></Icon>
