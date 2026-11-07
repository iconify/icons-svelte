<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng9-olbui.css';
import '../../css/s/s8d1qvbbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ng9-olbui"/><path class="s8d1qvbbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:delivery-bold" {...props}></Icon>
