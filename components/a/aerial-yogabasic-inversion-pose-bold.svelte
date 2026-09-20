<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnsadtbdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qnsadtbdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:aerial-yogabasic-inversion-pose-bold" {...props}></Icon>
