<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1gfmgbwj.css';
import '../../css/z/z_i6pn2af.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1gfmgbwj"/><path class="z_i6pn2af"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:medium" {...props}></Icon>
