<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxid0hx7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sxid0hx7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:headphones-solid" {...props}></Icon>
