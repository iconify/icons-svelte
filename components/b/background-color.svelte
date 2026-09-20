<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muybtqbir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-6,"top":-6};
const content = `<path class="muybtqbir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:background-color" {...props}></Icon>
