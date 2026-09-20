<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_dfj-bdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x_dfj-bdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:broken-heart-fill" {...props}></Icon>
