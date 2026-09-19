<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5a_1ab3h.css';
import '../../css/k/kdyg1ukjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t5a_1ab3h"/><path class="kdyg1ukjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:arrow-right" {...props}></Icon>
