<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jf_igcgqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jf_igcgqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:dots-vertical-filled" {...props}></Icon>
