<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uufo2obkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uufo2obkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cupcake-solid" {...props}></Icon>
