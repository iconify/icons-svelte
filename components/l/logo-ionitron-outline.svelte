<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brmy6cpyy.css';
import '../../css/p/p-6rxcb4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="brmy6cpyy"/><path class="p-6rxcb4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-ionitron-outline" {...props}></Icon>
