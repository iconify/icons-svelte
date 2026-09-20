<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv_y2cbfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xv_y2cbfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:microsoftaccess" {...props}></Icon>
