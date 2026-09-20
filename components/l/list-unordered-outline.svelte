<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hom7et23z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hom7et23z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:list-unordered-outline" {...props}></Icon>
