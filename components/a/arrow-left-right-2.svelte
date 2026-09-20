<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dp3su_b5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dp3su_b5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:arrow-left-right-2" {...props}></Icon>
