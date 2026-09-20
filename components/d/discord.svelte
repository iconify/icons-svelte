<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8d4mwbzs.css';
import '../../css/m/ml8_8mbod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8d4mwbzs"/><path class="ml8_8mbod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:discord" {...props}></Icon>
