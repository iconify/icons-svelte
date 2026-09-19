<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8jeuacsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="p8jeuacsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:currency-bangladeshi" {...props}></Icon>
