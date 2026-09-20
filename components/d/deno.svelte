<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt759hbpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bt759hbpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:deno" {...props}></Icon>
