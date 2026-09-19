<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7zfugz0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="y7zfugz0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:coffee" {...props}></Icon>
