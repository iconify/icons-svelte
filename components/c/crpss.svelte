<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvewf3boo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lvewf3boo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:crpss" {...props}></Icon>
