<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3qxd6b1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q3qxd6b1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:home-variant" {...props}></Icon>
