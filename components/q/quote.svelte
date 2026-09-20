<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iik18ybtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iik18ybtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:quote" {...props}></Icon>
