<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbs-egr_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lbs-egr_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:belarusian-ruble" {...props}></Icon>
