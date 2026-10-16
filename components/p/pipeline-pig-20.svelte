<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twj580cwe.css';
import '../../css/z/zfu5nqcgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="twj580cwe"/><path class="zfu5nqcgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pipeline-pig-20" {...props}></Icon>
