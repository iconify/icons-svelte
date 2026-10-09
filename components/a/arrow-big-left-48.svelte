<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w35slqbfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w35slqbfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-big-left-48" {...props}></Icon>
