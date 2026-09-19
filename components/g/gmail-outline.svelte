<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxwf4h5in.css';
import '../../css/b/bqf--ueux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vxwf4h5in"/><path clip-rule="evenodd" class="bqf--ueux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:gmail-outline" {...props}></Icon>
