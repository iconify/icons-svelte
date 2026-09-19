<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp6k_92sh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pp6k_92sh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:plug-connection" {...props}></Icon>
