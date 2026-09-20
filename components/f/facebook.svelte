<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgjnt5bfz.css';
import '../../css/y/y08ndqbqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rgjnt5bfz"/><path class="y08ndqbqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:facebook" {...props}></Icon>
