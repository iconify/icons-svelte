<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h02y9dblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1408};
const content = `<path class="h02y9dblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:cut" {...props}></Icon>
