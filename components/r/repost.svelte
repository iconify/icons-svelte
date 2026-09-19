<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa20eqbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oa20eqbcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:repost" {...props}></Icon>
