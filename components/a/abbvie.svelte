<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlb61lb8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zlb61lb8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:abbvie" {...props}></Icon>
