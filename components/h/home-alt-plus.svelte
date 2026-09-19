<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqvj4oear.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mqvj4oear"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:home-alt-plus" {...props}></Icon>
