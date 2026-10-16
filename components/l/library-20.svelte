<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0ni6vb5b.css';
import '../../css/e/edo682exk.css';
import '../../css/a/atrqkbbau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g0ni6vb5b"/><path class="edo682exk"/><path class="atrqkbbau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:library-20" {...props}></Icon>
