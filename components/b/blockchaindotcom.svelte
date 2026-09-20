<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euzyw7brh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="euzyw7brh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:blockchaindotcom" {...props}></Icon>
