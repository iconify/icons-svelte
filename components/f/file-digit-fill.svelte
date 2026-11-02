<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phhdg-b-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="phhdg-b-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-digit-fill" {...props}></Icon>
