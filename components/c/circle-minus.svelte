<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovu-g_vkt.css';
import '../../css/u/uivx-nb_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovu-g_vkt"/><path class="uivx-nb_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:circle-minus" {...props}></Icon>
