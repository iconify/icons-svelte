<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pg_3v5bbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pg_3v5bbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-right-up-linear" {...props}></Icon>
