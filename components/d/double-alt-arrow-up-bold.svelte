<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7rhdcbxy.css';
import '../../css/v/ve9aog86g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z7rhdcbxy"/><path class="ve9aog86g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:double-alt-arrow-up-bold" {...props}></Icon>
