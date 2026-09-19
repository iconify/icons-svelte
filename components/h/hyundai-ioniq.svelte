<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1f7g1lws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u1f7g1lws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:hyundai-ioniq" {...props}></Icon>
