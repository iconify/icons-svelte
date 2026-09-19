<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aj-aobbhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="aj-aobbhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:grid" {...props}></Icon>
