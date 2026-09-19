<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdf4g625i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdf4g625i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:dialpad" {...props}></Icon>
