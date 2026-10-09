<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6y4q0buk.css';
import '../../css/y/ykgt55trn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f6y4q0buk"/><path class="ykgt55trn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rolling-pin-48-bold" {...props}></Icon>
