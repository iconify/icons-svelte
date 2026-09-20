<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/domlw-b2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":580,"height":580};
const content = `<path class="domlw-b2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ragas" {...props}></Icon>
