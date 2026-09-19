<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxwkt6myp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxwkt6myp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:restroom-men" {...props}></Icon>
