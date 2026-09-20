<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpmurq.css';
import '../../css/s/so-from-16.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kpmurq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:minus" {...props}></Icon>
