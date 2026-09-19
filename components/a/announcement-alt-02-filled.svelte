<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl6gc6mhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bl6gc6mhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:announcement-alt-02-filled" {...props}></Icon>
