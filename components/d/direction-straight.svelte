<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm0aez-8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hm0aez-8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:direction-straight" {...props}></Icon>
