<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-y12rbii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-y12rbii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:mouse-filled" {...props}></Icon>
