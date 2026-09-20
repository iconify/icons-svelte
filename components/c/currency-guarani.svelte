<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nu1lb4brs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nu1lb4brs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:currency-guarani" {...props}></Icon>
