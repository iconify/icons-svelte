<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5wc5cr_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z5wc5cr_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:phone-off" {...props}></Icon>
