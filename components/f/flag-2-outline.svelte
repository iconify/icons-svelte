<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2x94pt6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r2x94pt6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:flag-2-outline" {...props}></Icon>
