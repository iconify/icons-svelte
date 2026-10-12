<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbryi_wln.css';
import '../../css/a/a897-ob1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pbryi_wln"/><path class="a897-ob1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pill-20" {...props}></Icon>
