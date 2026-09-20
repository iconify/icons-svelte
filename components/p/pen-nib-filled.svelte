<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-w8tuyfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u-w8tuyfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:pen-nib-filled" {...props}></Icon>
