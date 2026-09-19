<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jk33kthvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jk33kthvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:mode-dark-fill" {...props}></Icon>
