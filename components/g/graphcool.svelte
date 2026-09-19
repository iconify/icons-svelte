<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kweki9fds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kweki9fds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:graphcool" {...props}></Icon>
