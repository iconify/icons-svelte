<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwnfrebag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwnfrebag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:danger" {...props}></Icon>
