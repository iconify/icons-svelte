<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdz7ccbvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":1024};
const content = `<path class="cdz7ccbvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:robocop" {...props}></Icon>
