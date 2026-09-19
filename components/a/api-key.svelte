<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m223cpbhr.css';
import '../../css/p/pr_1mzb5o.css';
import '../../css/c/cc-gngndl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m223cpbhr"/><circle class="pr_1mzb5o"/><path class="cc-gngndl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:api-key" {...props}></Icon>
