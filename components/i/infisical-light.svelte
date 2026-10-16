<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb9sfrenb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":91,"height":43};
const content = `<path class="nb9sfrenb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:infisical-light" {...props}></Icon>
