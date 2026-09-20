<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3xlq9bor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3xlq9bor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cloud-cog" {...props}></Icon>
