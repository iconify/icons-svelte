<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2j0hv8wh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z2j0hv8wh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:database-import" {...props}></Icon>
