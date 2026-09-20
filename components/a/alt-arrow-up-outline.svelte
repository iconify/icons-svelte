<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhx05rsiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rhx05rsiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:alt-arrow-up-outline" {...props}></Icon>
