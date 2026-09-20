<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujw1_grww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ujw1_grww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:puppy" {...props}></Icon>
