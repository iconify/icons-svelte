<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0g4dobjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d0g4dobjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:mail-cog-solid" {...props}></Icon>
