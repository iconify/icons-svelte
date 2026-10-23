<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7r6s5lmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z7r6s5lmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:file-exclamation-point" {...props}></Icon>
