<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-2-zob9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-2-zob9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-box-edit-outline" {...props}></Icon>
