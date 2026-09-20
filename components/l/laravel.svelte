<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thytvacbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":264};
const content = `<path class="thytvacbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:laravel" {...props}></Icon>
