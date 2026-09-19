<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9-buhbhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":704,"height":1024};
const content = `<path class="h9-buhbhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:lifehacker" {...props}></Icon>
