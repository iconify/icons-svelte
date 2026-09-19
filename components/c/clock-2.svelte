<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k18y-k1ul.css';
import '../../css/g/g0hn70dyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k18y-k1ul"/><path class="g0hn70dyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:clock-2" {...props}></Icon>
