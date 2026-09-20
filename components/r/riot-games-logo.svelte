<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqqyqm4-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lqqyqm4-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:riot-games-logo" {...props}></Icon>
