<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwj7unb0w.css';
import '../../css/q/q0jqwwdlw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pwj7unb0w"/><path class="q0jqwwdlw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nixos" {...props}></Icon>
