<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnop98bbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jnop98bbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:device-database-encryption-1" {...props}></Icon>
