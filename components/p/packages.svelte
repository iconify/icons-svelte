<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4w3txb9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g4w3txb9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:packages" {...props}></Icon>
