<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbd7tvy7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sbd7tvy7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:border-right-02" {...props}></Icon>
