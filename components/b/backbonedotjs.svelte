<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k57ycp3nx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k57ycp3nx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:backbonedotjs" {...props}></Icon>
