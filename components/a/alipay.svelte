<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm0c_-b-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nm0c_-b-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:alipay" {...props}></Icon>
