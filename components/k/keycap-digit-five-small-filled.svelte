<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc806c_2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="rc806c_2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-digit-five-small-filled" {...props}></Icon>
