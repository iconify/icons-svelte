<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfkd-0bbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mfkd-0bbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:figshare" {...props}></Icon>
