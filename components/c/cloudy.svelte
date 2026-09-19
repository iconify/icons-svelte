<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxxksqb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pxxksqb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:cloudy" {...props}></Icon>
