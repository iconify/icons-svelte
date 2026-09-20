<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8p-xymns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s8p-xymns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:download" {...props}></Icon>
