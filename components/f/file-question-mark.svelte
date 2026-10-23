<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skjqw1bpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="skjqw1bpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:file-question-mark" {...props}></Icon>
