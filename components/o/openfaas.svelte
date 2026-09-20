<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi-4w3bku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fi-4w3bku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:openfaas" {...props}></Icon>
