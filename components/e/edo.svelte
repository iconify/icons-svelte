<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl5ob1sld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nl5ob1sld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:edo" {...props}></Icon>
