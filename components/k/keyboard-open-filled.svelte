<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t885h7bha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t885h7bha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:keyboard-open-filled" {...props}></Icon>
