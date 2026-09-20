<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5bzhc2yk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e5bzhc2yk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:fig" {...props}></Icon>
