<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnjxs1h6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qnjxs1h6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:graylog-light" {...props}></Icon>
