<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo1ap9bgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mo1ap9bgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:google-drive-light" {...props}></Icon>
