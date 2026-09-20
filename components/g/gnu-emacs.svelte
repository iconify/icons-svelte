<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7vaibc6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m7vaibc6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gnu-emacs" {...props}></Icon>
