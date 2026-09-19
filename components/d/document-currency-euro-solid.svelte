<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnnsfxb0b.css';
import '../../css/t/t4ibq1bzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pnnsfxb0b"/><path class="t4ibq1bzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:document-currency-euro-solid" {...props}></Icon>
