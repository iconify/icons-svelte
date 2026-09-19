<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5h6isb2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="g5h6isb2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:nhibernate" {...props}></Icon>
