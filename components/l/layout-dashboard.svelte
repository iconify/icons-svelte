<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xogm_7b8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xogm_7b8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:layout-dashboard" {...props}></Icon>
