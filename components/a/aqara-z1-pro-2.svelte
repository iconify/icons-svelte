<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqe3nzz0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mqe3nzz0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-z1-pro-2" {...props}></Icon>
