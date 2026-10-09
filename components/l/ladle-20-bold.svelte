<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-jm55j8c.css';
import '../../css/j/j-o8fhbra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k-jm55j8c"/><path class="j-o8fhbra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ladle-20-bold" {...props}></Icon>
