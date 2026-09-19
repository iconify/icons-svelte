<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5ilorl2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u5ilorl2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:arrow-up" {...props}></Icon>
