<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jf2sa2bjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jf2sa2bjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:expand" {...props}></Icon>
