<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3kv63imc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d3kv63imc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:library-24" {...props}></Icon>
