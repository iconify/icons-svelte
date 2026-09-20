<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kj9ymybmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kj9ymybmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-letter-c-filled" {...props}></Icon>
