<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7nfih-ms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r7nfih-ms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:csv-file-filled" {...props}></Icon>
