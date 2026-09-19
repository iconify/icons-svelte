<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdvibimmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mdvibimmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:payment-method" {...props}></Icon>
