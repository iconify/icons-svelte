<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgmgv-b8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xgmgv-b8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:phone-x-mark" {...props}></Icon>
