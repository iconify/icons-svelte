<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/is__0acte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="is__0acte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:cenz" {...props}></Icon>
