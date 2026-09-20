<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3gib6vnb.css';
import '../../css/j/jh04-5upe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v3gib6vnb"/><path class="jh04-5upe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-content-open" {...props}></Icon>
