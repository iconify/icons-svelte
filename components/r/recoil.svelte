<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/beynuj9wr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="beynuj9wr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:recoil" {...props}></Icon>
