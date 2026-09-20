<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b09a7qbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b09a7qbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:ana" {...props}></Icon>
