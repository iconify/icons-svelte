<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjqloignw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":896};
const content = `<path class="bjqloignw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:photosphere" {...props}></Icon>
