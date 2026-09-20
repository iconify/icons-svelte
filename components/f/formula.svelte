<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1u5zqbzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1u5zqbzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:formula" {...props}></Icon>
