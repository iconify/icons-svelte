<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ziaj1qlxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ziaj1qlxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:gimp" {...props}></Icon>
