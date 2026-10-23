<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ima60vbta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ima60vbta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:database-arrow-down" {...props}></Icon>
