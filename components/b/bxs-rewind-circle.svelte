<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_4z2nb_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x_4z2nb_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-rewind-circle" {...props}></Icon>
