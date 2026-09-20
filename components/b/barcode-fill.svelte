<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kl4fr1byu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kl4fr1byu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:barcode-fill" {...props}></Icon>
