<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ej8uesbmu.css';
import '../../css/d/dgaovib7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ej8uesbmu"/><path class="dgaovib7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-twitch-outline" {...props}></Icon>
