<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6fkriojo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g6fkriojo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-down-right-02" {...props}></Icon>
