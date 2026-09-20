<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9v3uqbfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f9v3uqbfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:golf-tee" {...props}></Icon>
