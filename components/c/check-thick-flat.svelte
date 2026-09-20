<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_uzzupcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o_uzzupcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:check-thick-flat" {...props}></Icon>
