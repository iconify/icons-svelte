<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe030ibzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xe030ibzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:octogon-filled-16" {...props}></Icon>
