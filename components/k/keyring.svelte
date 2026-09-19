<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd8ircw_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yd8ircw_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:keyring" {...props}></Icon>
