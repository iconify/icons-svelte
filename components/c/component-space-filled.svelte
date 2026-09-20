<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_ql564gm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_ql564gm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:component-space-filled" {...props}></Icon>
