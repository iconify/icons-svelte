<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwt1mrh8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="uwt1mrh8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:cakephp" {...props}></Icon>
