<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1iyjg9mm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1iyjg9mm primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:folder-duotone" {...props}></Icon>
