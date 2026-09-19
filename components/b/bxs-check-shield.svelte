<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3gx5pbdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n3gx5pbdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-check-shield" {...props}></Icon>
