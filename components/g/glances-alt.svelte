<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sav88e29u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sav88e29u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:glances-alt" {...props}></Icon>
