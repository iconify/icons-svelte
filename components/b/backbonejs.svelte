<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yj95wxtxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="yj95wxtxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:backbonejs" {...props}></Icon>
