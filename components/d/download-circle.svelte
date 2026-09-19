<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ga9gewffn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ga9gewffn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:download-circle" {...props}></Icon>
