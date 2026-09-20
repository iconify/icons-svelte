<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lor2r5p4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lor2r5p4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:multiple-neutral-2" {...props}></Icon>
