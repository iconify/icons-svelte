<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg3giegrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fg3giegrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:polygon" {...props}></Icon>
