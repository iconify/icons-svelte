<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsn_blbny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsn_blbny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:netcup" {...props}></Icon>
