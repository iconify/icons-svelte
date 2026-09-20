<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btqb3741s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="btqb3741s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bounce-right-filled" {...props}></Icon>
