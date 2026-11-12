<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/io7dnibtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="io7dnibtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bookmark-x" {...props}></Icon>
