<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-oonistw.css';
import '../../css/b/b9083lrix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n-oonistw"/><path class="b9083lrix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crane-hook-20" {...props}></Icon>
