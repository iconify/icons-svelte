<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2a6qzlrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r2a6qzlrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:notifications-alt-fill" {...props}></Icon>
