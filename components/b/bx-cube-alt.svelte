<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecstjpb2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ecstjpb2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-cube-alt" {...props}></Icon>
