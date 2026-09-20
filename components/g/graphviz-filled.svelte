<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clwxsqbko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="clwxsqbko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:graphviz-filled" {...props}></Icon>
