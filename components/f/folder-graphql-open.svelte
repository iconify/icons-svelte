<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-4zo-uap.css';
import '../../css/m/m3lvxtb4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w-4zo-uap"/><path class="m3lvxtb4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-graphql-open" {...props}></Icon>
