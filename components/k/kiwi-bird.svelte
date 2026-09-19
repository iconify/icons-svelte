<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tera5-bjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="tera5-bjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:kiwi-bird" {...props}></Icon>
