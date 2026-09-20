<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cceytw1-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cceytw1-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:akasaair" {...props}></Icon>
