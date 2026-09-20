<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h35seqbyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="h35seqbyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:directions" {...props}></Icon>
