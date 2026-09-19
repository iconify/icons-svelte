<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3j_08rws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="p3j_08rws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:disqus" {...props}></Icon>
