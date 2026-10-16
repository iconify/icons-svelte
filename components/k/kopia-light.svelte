<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9daaw4ne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":64};
const content = `<path class="w9daaw4ne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kopia-light" {...props}></Icon>
