<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iu8ot3m7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iu8ot3m7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:link-circle-bold" {...props}></Icon>
