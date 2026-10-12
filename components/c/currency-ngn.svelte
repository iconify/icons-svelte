<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8e0dfngy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u8e0dfngy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:currency-ngn" {...props}></Icon>
