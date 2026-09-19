<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwbzpyb5i.css';
import '../../css/p/pr_1mzb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wwbzpyb5i"/><circle class="pr_1mzb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:password" {...props}></Icon>
