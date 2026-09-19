<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l587qenuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l587qenuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:pentagon-up" {...props}></Icon>
