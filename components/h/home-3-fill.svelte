<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6qkfpwoo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k6qkfpwoo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:home-3-fill" {...props}></Icon>
