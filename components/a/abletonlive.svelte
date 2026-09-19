<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3w0o-4uq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h3w0o-4uq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:abletonlive" {...props}></Icon>
