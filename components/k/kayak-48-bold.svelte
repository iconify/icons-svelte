<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9903qb7k.css';
import '../../css/u/uwd9spbxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b9903qb7k"/><path class="uwd9spbxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:kayak-48-bold" {...props}></Icon>
