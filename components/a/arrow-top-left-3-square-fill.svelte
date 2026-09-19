<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr5x2bcqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cr5x2bcqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-top-left-3-square-fill" {...props}></Icon>
