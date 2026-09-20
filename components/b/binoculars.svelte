<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mps6rsbwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mps6rsbwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:binoculars" {...props}></Icon>
