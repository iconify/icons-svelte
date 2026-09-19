<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qugix2k9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="qugix2k9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:archive" {...props}></Icon>
