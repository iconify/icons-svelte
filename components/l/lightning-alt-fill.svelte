<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxojb-bjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxojb-bjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:lightning-alt-fill" {...props}></Icon>
