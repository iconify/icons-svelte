<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea5taoauh.css';
import '../../css/z/zel29wb1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ea5taoauh secondary"/><path class="primary zel29wb1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:heart-duo" {...props}></Icon>
