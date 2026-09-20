<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agz0d01mv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="agz0d01mv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pentagon-plus" {...props}></Icon>
