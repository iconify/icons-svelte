<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzho85dns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jzho85dns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-edit-alt-2-line" {...props}></Icon>
