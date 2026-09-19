<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg8tdmqjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gg8tdmqjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:cpanel" {...props}></Icon>
