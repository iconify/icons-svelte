<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0un0rskt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h0un0rskt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:reddit-alien-alt" {...props}></Icon>
