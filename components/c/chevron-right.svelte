<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xl1__qb0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xl1__qb0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:chevron-right" {...props}></Icon>
