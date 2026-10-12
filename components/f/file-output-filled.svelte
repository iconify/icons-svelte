<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xaxmjgbje.css';
import '../../css/o/ofusmvbko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xaxmjgbje"/><path class="ofusmvbko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:file-output-filled" {...props}></Icon>
