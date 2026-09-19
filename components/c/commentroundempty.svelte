<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/daoyp4bub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="daoyp4bub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:commentroundempty" {...props}></Icon>
