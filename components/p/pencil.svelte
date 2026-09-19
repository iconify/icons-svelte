<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swny0lthw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="swny0lthw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:pencil" {...props}></Icon>
