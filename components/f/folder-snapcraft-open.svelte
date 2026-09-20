<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-fmsbcaz.css';
import '../../css/u/ungtlkbnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p-fmsbcaz"/><path class="ungtlkbnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-snapcraft-open" {...props}></Icon>
