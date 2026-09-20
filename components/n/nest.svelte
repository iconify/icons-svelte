<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcya0gqwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tcya0gqwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:nest" {...props}></Icon>
