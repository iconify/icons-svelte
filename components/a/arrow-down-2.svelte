<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_dz3ub_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f_dz3ub_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-down-2" {...props}></Icon>
