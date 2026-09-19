<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wuhjp4b3q.css';
import '../../css/s/sx7umwbzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wuhjp4b3q"/><path class="sx7umwbzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:finger-touch" {...props}></Icon>
