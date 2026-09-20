<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bof_92yus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bof_92yus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:asterisk-diamond-solid" {...props}></Icon>
