<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb3h9qxze.css';
import '../../css/w/wru8zmbec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kb3h9qxze"/><path clip-rule="evenodd" class="wru8zmbec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:home-angle-outline" {...props}></Icon>
