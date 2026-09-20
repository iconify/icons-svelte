<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bazfj2bff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bazfj2bff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-menu-fill" {...props}></Icon>
