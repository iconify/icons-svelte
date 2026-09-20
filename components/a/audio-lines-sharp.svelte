<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz1dp7iva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lz1dp7iva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:audio-lines-sharp" {...props}></Icon>
