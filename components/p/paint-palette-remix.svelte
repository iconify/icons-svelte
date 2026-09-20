<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7n416b3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="z7n416b3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:paint-palette-remix" {...props}></Icon>
