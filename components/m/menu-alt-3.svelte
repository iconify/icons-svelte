<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1ofg2bcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k1ofg2bcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:menu-alt-3" {...props}></Icon>
