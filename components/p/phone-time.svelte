<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tas58qb1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tas58qb1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:phone-time" {...props}></Icon>
