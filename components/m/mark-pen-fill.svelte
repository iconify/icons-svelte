<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwjbk1txm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nwjbk1txm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mark-pen-fill" {...props}></Icon>
