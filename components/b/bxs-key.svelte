<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8w1hpbco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8w1hpbco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-key" {...props}></Icon>
