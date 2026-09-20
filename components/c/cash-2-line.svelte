<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc7lxnfds.css';
import '../../css/u/u-06obvoh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jc7lxnfds"/><path class="u-06obvoh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cash-2-line" {...props}></Icon>
