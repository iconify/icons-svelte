<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in919sbiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="in919sbiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:file-spreadsheet" {...props}></Icon>
