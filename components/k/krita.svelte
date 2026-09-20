<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6jgu_d1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a6jgu_d1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:krita" {...props}></Icon>
