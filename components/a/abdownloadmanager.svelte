<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcnb0lbwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcnb0lbwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:abdownloadmanager" {...props}></Icon>
