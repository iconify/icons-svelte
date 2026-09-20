<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/celdv5lhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="celdv5lhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:case-small-caps-16" {...props}></Icon>
