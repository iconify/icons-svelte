<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfe-3o5hh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfe-3o5hh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:compare-size" {...props}></Icon>
