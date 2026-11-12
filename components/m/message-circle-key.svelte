<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq-l9svud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fq-l9svud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:message-circle-key" {...props}></Icon>
