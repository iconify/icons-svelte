<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5ej_tn8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x5ej_tn8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:currency-rupee" {...props}></Icon>
