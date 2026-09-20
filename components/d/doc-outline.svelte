<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qt-uee45l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qt-uee45l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:doc-outline" {...props}></Icon>
