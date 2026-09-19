<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd5ux5bbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="hd5ux5bbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-return-small-filled" {...props}></Icon>
