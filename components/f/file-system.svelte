<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q80xw6b5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q80xw6b5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:file-system" {...props}></Icon>
