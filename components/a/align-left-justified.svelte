<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u96qf2b8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u96qf2b8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:align-left-justified" {...props}></Icon>
