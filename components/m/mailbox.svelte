<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akij6mbzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="akij6mbzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:mailbox" {...props}></Icon>
