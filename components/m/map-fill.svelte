<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/of74y6r7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="of74y6r7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:map-fill" {...props}></Icon>
