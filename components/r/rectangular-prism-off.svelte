<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6aj__i7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v6aj__i7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:rectangular-prism-off" {...props}></Icon>
