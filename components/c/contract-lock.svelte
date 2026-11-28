<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyjz8j-0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pyjz8j-0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:contract-lock" {...props}></Icon>
