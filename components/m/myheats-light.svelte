<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qz15a5bue.css';
import '../../css/h/hvvzmxb9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qz15a5bue"/><path class="hvvzmxb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:myheats-light" {...props}></Icon>
