<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkqg-thzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zkqg-thzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:impact" {...props}></Icon>
