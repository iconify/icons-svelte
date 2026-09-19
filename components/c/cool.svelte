<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms1t--bpr.css';
import '../../css/h/h9o6htbtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ms1t--bpr"/><path class="h9o6htbtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cool" {...props}></Icon>
