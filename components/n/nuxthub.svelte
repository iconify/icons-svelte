<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxeyuembw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":49,"height":33};
const content = `<path clip-rule="evenodd" class="bxeyuembw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nuxthub" {...props}></Icon>
