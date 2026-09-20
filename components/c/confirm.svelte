<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gydqkw.css';
import '../../css/s/so-from-26.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gydqkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:confirm" {...props}></Icon>
