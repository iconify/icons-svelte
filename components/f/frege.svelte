<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqss8kh_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":441,"height":512};
const content = `<path class="tqss8kh_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:frege" {...props}></Icon>
