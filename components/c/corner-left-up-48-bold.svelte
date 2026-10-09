<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1uuebynj.css';
import '../../css/s/se19vpb9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z1uuebynj"/><path class="se19vpb9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:corner-left-up-48-bold" {...props}></Icon>
