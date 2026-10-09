<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guj_uobue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="guj_uobue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:direct-current-48-bold" {...props}></Icon>
