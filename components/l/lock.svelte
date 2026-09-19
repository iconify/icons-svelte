<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk9mcoe9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1152,"height":1408};
const content = `<path class="fk9mcoe9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:lock" {...props}></Icon>
