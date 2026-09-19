<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9ul6rwle.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x9ul6rwle"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:cloud-generic" {...props}></Icon>
