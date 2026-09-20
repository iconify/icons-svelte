<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggl5p0bvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ggl5p0bvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:label" {...props}></Icon>
