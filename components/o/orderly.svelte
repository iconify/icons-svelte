<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vf1lmlcvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vf1lmlcvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:orderly" {...props}></Icon>
