<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfid2qr4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sfid2qr4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:gofundme" {...props}></Icon>
