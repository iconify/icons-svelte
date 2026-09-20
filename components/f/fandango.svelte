<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un5bcwbkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="un5bcwbkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fandango" {...props}></Icon>
