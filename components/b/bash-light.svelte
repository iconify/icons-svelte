<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adaitknsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="adaitknsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bash-light" {...props}></Icon>
