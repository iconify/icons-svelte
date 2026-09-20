<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovp2cqbju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ovp2cqbju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:curling-stone" {...props}></Icon>
