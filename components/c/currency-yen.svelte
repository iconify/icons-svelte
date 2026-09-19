<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7b_veb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="h7b_veb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:currency-yen" {...props}></Icon>
