<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ady9k8bfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ady9k8bfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:linkedin" {...props}></Icon>
