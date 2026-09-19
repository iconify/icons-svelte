<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8_3nubjg.css';
import '../../css/s/skvu_5_5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o8_3nubjg"/><path class="skvu_5_5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:football" {...props}></Icon>
