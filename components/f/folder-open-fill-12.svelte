<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mblcg4bnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="mblcg4bnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:folder-open-fill-12" {...props}></Icon>
