<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae99qnlul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ae99qnlul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-multiple" {...props}></Icon>
