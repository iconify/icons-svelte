<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trw6j0drs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="trw6j0drs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:a1-mini" {...props}></Icon>
