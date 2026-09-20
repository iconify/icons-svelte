<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvkbhebit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":386,"height":390};
const content = `<path clip-rule="evenodd" class="cvkbhebit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:goil-dark" {...props}></Icon>
