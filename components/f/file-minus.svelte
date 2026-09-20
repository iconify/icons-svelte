<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gm6wtzeab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gm6wtzeab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:file-minus" {...props}></Icon>
