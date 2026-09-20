<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mh5vc8h5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mh5vc8h5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:petri-dish-2-bold" {...props}></Icon>
