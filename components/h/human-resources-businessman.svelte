<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnd0a-8mb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pnd0a-8mb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:human-resources-businessman" {...props}></Icon>
