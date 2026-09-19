<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-96robzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="o-96robzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:archlinux" {...props}></Icon>
