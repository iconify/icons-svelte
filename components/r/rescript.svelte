<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq9by0bzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pq9by0bzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:rescript" {...props}></Icon>
