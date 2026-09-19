<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2muvqext.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":832,"height":1024};
const content = `<path class="x2muvqext"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:boxtrapper" {...props}></Icon>
