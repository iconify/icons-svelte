<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wiuwblb7l.css';
import '../../css/z/zy_wagb-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wiuwblb7l"/><path class="zy_wagb-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:fetch-upload" {...props}></Icon>
