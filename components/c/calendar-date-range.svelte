<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgj0nj_cz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hgj0nj_cz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:calendar-date-range" {...props}></Icon>
