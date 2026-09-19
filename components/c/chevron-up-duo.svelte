<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5z2_x_sp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5z2_x_sp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:chevron-up-duo" {...props}></Icon>
