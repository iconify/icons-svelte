<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gx-u50amq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="gx-u50amq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-digit-zero-small-filled" {...props}></Icon>
