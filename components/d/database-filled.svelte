<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvezwc7ew.css';
import '../../css/u/uemg9fbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xvezwc7ew"/><path class="uemg9fbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:database-filled" {...props}></Icon>
