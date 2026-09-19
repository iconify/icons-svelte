<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_6x1nbxh.css';
import '../../css/k/k18y-k1ul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a_6x1nbxh"/><path class="k18y-k1ul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:circle-chev-left" {...props}></Icon>
