<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4vq98bmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i4vq98bmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:more" {...props}></Icon>
