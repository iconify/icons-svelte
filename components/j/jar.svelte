<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1t180kcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="u1t180kcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:jar" {...props}></Icon>
