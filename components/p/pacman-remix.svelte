<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd8rjt12r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="bd8rjt12r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:pacman-remix" {...props}></Icon>
