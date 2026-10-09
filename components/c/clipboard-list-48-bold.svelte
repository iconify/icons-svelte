<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adm1b9bzj.css';
import '../../css/u/u46oqbc7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="adm1b9bzj"/><path class="u46oqbc7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:clipboard-list-48-bold" {...props}></Icon>
