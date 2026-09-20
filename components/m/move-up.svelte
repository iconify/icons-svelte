<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otgl_qb9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="otgl_qb9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:move-up" {...props}></Icon>
