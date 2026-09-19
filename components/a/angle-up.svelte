<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kddvl9o6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kddvl9o6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:angle-up" {...props}></Icon>
