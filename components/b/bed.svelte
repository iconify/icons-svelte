<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd0sfqb_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wd0sfqb_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:bed" {...props}></Icon>
