<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozq0t_xbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ozq0t_xbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:pricetags-fill" {...props}></Icon>
