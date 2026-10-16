<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6nep0q5q.css';
import '../../css/m/m0scgbc4g.css';
import '../../css/v/v8vdtjh7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e6nep0q5q"/><path class="m0scgbc4g"/><path class="v8vdtjh7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:reply-all-20-bold" {...props}></Icon>
