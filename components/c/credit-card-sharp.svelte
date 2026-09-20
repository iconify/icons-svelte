<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfgy3dwww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zfgy3dwww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:credit-card-sharp" {...props}></Icon>
