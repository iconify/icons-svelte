<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjvnp3bmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wjvnp3bmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:hotel-search" {...props}></Icon>
