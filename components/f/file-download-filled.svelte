<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs0ufybth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qs0ufybth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:file-download-filled" {...props}></Icon>
