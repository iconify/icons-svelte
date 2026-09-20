<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpub25bol.css';
import '../../css/j/jqfr0dnja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kpub25bol"/><path class="jqfr0dnja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-trash-open" {...props}></Icon>
