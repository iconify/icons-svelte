<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yoezm8bqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yoezm8bqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:currency-uah" {...props}></Icon>
