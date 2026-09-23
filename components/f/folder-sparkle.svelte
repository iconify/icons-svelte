<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-_e-j4zc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-_e-j4zc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:folder-sparkle" {...props}></Icon>
