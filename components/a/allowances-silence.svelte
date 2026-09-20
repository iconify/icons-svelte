<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emd2fydgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="emd2fydgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:allowances-silence" {...props}></Icon>
