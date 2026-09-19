<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zeoe7r16d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zeoe7r16d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:credit-card-front" {...props}></Icon>
