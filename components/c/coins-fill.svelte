<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_ynj8bzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_ynj8bzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:coins-fill" {...props}></Icon>
