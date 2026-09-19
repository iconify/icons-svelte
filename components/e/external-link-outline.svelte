<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2b_x2s3y.css';
import '../../css/c/cu9m93g4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o2b_x2s3y"/><path class="cu9m93g4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:external-link-outline" {...props}></Icon>
