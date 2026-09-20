<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs_4bcclq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xs_4bcclq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chevron-up-waves-solid" {...props}></Icon>
