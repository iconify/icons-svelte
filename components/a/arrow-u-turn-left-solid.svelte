<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zir9xpbua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zir9xpbua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-u-turn-left-solid" {...props}></Icon>
