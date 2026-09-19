<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzv3d8bcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bzv3d8bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:receipt-percent-solid" {...props}></Icon>
