<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ls9cc-bhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ls9cc-bhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:phone-pause" {...props}></Icon>
