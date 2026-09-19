<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlzqv1cqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jlzqv1cqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:less" {...props}></Icon>
