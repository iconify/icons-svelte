<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv1-4q61b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nv1-4q61b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:git" {...props}></Icon>
