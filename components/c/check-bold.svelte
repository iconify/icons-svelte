<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncrj0nj_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ncrj0nj_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:check-bold" {...props}></Icon>
