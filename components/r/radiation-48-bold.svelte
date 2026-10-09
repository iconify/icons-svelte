<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r86gyghte.css';
import '../../css/n/nkn0wyb7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r86gyghte"/><path class="nkn0wyb7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:radiation-48-bold" {...props}></Icon>
