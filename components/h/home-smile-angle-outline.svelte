<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_en--b-n.css';
import '../../css/w/wru8zmbec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_en--b-n"/><path clip-rule="evenodd" class="wru8zmbec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:home-smile-angle-outline" {...props}></Icon>
