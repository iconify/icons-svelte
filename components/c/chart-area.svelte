<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxny0p36e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kxny0p36e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:chart-area" {...props}></Icon>
