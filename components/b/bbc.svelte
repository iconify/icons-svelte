<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi_lh7bxp.css';
import '../../css/l/lu06jwoxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xi_lh7bxp"/><path class="lu06jwoxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:bbc" {...props}></Icon>
