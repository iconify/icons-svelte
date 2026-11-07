<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2-x-cbeh.css';
import '../../css/f/fhhc7bnyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j2-x-cbeh"/><path class="fhhc7bnyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:grid-3x2-bold-duotone" {...props}></Icon>
