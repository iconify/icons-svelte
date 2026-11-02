<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1pc572vn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v1pc572vn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:certificate-fill" {...props}></Icon>
