<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbsqho_bp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qbsqho_bp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:document-currency-bangladeshi-16-solid" {...props}></Icon>
