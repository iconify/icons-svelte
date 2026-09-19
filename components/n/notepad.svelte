<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl7z0xbvn.css';
import '../../css/y/y07exzb3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nl7z0xbvn"/><path class="y07exzb3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:notepad" {...props}></Icon>
