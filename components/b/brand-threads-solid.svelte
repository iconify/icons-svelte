<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7v68xb2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k7v68xb2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:brand-threads-solid" {...props}></Icon>
