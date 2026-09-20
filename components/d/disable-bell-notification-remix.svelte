<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz7bdnbih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pz7bdnbih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:disable-bell-notification-remix" {...props}></Icon>
