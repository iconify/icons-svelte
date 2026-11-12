<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjs6soxtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kjs6soxtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-mobile-key" {...props}></Icon>
