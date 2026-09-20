<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksa64jblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ksa64jblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:dots-2x2-solid" {...props}></Icon>
