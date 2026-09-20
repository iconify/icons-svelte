<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm7z1311u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fm7z1311u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:image-toolbox" {...props}></Icon>
