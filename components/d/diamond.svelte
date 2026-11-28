<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecmg8sbjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ecmg8sbjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:diamond" {...props}></Icon>
