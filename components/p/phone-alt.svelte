<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/volby5qpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="volby5qpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:phone-alt" {...props}></Icon>
