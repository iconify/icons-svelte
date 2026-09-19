<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9jkhxbmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":23,"height":24};
const content = `<path class="o9jkhxbmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:angle-dobule-down" {...props}></Icon>
