<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-al7jbls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-al7jbls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:codechef" {...props}></Icon>
