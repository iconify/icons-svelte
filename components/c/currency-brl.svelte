<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsd7icbda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qsd7icbda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:currency-brl" {...props}></Icon>
