<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1s7b7bnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h1s7b7bnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:plus-circle-fill" {...props}></Icon>
