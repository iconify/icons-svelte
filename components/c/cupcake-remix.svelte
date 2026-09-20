<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js8ju-e_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="js8ju-e_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:cupcake-remix" {...props}></Icon>
