<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqvhg5dzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqvhg5dzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:home-alt-outline" {...props}></Icon>
