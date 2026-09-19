<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpe_dfizg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qpe_dfizg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:currency-euro-solid" {...props}></Icon>
