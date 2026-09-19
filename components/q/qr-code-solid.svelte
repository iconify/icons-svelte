<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7_ed9k0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t7_ed9k0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:qr-code-solid" {...props}></Icon>
