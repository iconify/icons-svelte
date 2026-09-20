<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9fl78bjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t9fl78bjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-dolby-digital" {...props}></Icon>
