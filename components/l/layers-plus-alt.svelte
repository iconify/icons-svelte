<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/piom46bco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="piom46bco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:layers-plus-alt" {...props}></Icon>
