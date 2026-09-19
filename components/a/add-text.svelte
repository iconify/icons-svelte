<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7mgxib6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s7mgxib6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:add-text" {...props}></Icon>
