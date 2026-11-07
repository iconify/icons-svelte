<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ust9b7bnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ust9b7bnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:alt-arrow-right-outline" {...props}></Icon>
