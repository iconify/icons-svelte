<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk6-szb_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fk6-szb_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:home-to-cloud-sync" {...props}></Icon>
