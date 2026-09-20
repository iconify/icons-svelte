<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to656dbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="to656dbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-t-octagon-solid" {...props}></Icon>
