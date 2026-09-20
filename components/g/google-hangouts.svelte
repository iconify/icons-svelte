<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntzcl4b-u.css';
import '../../css/g/gjisevbwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ntzcl4b-u"/><path class="gjisevbwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:google-hangouts" {...props}></Icon>
