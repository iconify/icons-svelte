<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1pz90bnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="c1pz90bnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:dentist-11" {...props}></Icon>
