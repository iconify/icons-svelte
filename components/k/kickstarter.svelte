<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1em5i3_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="w1em5i3_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:kickstarter" {...props}></Icon>
