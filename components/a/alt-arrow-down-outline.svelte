<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psze7x7uo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="psze7x7uo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:alt-arrow-down-outline" {...props}></Icon>
