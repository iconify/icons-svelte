<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8tuk2fcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="o8tuk2fcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-windows-small" {...props}></Icon>
