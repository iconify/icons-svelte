<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud3cc5b0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ud3cc5b0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:relay" {...props}></Icon>
