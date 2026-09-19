<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-s69c4hn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-s69c4hn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:phone-fast-filled" {...props}></Icon>
