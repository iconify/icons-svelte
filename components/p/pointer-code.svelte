<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0lep8jzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0lep8jzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pointer-code" {...props}></Icon>
