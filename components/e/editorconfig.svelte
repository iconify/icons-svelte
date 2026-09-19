<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy1cqobue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gy1cqobue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:editorconfig" {...props}></Icon>
