<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdab_2s4t.css';
import '../../css/p/py210wb6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zdab_2s4t"/><path class="py210wb6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:paragraph-48" {...props}></Icon>
