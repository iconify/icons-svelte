<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzgjo3w_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzgjo3w_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:exclamation-circle-outline" {...props}></Icon>
