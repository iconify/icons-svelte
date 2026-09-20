<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_w-hxjse.css';
import '../../css/z/zbx9303xv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_w-hxjse"/><path class="zbx9303xv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:bug-solid" {...props}></Icon>
