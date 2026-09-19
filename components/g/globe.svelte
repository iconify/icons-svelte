<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpryfp0ky.css';
import '../../css/o/omiz2rshg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bpryfp0ky"/><path class="omiz2rshg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:globe" {...props}></Icon>
