<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-0us7bcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-0us7bcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:mail-sharp" {...props}></Icon>
