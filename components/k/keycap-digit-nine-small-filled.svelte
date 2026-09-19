<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yoa8cbekc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="yoa8cbekc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-digit-nine-small-filled" {...props}></Icon>
