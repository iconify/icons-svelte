<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/foozhp2ty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="foozhp2ty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:baidu" {...props}></Icon>
