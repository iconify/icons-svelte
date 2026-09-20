<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm2f1wbjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qm2f1wbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:message-report" {...props}></Icon>
