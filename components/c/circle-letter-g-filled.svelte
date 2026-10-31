<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjo0s3sqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mjo0s3sqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-letter-g-filled" {...props}></Icon>
