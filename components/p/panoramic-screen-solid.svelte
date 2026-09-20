<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9uf-q8uh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="t9uf-q8uh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:panoramic-screen-solid" {...props}></Icon>
