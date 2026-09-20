<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct1ofye1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="ct1ofye1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:at-symbol" {...props}></Icon>
