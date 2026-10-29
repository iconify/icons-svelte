<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inj1tcbzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="inj1tcbzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:message-circle-question-solid" {...props}></Icon>
