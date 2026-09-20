<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmz93sk0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmz93sk0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:message-minus-outline" {...props}></Icon>
