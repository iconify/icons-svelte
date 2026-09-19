<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3brg2cab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n3brg2cab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:bathtub" {...props}></Icon>
