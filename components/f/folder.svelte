<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_44zqbvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1391,"height":1000};
const content = `<path class="x_44zqbvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:folder" {...props}></Icon>
