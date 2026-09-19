<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd60nacpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xd60nacpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:arrow-up-right-circle-solid" {...props}></Icon>
