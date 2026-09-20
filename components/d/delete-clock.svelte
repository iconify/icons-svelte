<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqd6b-bhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pqd6b-bhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:delete-clock" {...props}></Icon>
