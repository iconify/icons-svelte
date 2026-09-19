<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4dgxacwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h4dgxacwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:document-currency-bangladeshi-solid" {...props}></Icon>
