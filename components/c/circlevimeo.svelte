<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hk9jk_8nt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hk9jk_8nt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circlevimeo" {...props}></Icon>
