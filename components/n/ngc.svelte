<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eer8ncbtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eer8ncbtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ngc" {...props}></Icon>
