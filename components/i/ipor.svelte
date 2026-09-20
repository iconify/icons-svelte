<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2mwzrbfn.css';
import '../../css/q/qu61xsbqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a2mwzrbfn"/><path class="qu61xsbqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ipor" {...props}></Icon>
