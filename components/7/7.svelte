<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmh7oqbps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":467,"height":754};
const content = `<path class="gmh7oqbps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:7" {...props}></Icon>
