<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpd-y_4wx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kpd-y_4wx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:package-plus" {...props}></Icon>
