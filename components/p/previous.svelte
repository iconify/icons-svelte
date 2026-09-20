<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7jcc9bye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x7jcc9bye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:previous" {...props}></Icon>
