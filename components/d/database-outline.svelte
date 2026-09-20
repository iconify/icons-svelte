<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0mf4bbzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p0mf4bbzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:database-outline" {...props}></Icon>
