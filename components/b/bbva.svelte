<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krxl8tomz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":3543.2,"height":1059.5};
const content = `<path class="krxl8tomz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bbva" {...props}></Icon>
