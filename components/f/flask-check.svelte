<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrr95lbgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lrr95lbgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:flask-check" {...props}></Icon>
