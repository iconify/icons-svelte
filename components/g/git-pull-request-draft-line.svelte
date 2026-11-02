<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2wim-bik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t2wim-bik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:git-pull-request-draft-line" {...props}></Icon>
