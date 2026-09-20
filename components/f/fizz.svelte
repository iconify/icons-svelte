<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdx5jchok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fdx5jchok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:fizz" {...props}></Icon>
