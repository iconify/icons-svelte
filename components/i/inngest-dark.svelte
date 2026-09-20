<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb2av2t2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":30};
const content = `<path clip-rule="evenodd" class="wb2av2t2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:inngest-dark" {...props}></Icon>
