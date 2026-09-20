<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khg_sbbeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="khg_sbbeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chevron-up-down-solid" {...props}></Icon>
