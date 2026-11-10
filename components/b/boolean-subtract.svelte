<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tne-w562i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tne-w562i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:boolean-subtract" {...props}></Icon>
