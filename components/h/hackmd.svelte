<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osy670bcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="osy670bcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:hackmd" {...props}></Icon>
