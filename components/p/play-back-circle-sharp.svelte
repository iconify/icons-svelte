<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/as7rq8bai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="as7rq8bai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:play-back-circle-sharp" {...props}></Icon>
