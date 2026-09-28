<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atouqacem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="atouqacem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:groin-with-rememberance-ribbon" {...props}></Icon>
