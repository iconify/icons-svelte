<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6kb-tklu.css';
import '../../css/s/s6r4foaoj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n6kb-tklu"/><path class="s6r4foaoj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:launch" {...props}></Icon>
