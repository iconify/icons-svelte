<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnnr_6bez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lnnr_6bez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:finger-print-solid" {...props}></Icon>
