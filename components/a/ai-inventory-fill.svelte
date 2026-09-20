<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v463yrbvf.css';
import '../../css/q/qat1j1bpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v463yrbvf"/><path clip-rule="evenodd" class="qat1j1bpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-inventory-fill" {...props}></Icon>
