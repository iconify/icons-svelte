<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn_mdboia.css';
import '../../css/k/k78ldxeyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nn_mdboia"/><path class="k78ldxeyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:food-drink-fish" {...props}></Icon>
