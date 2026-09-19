<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qos0h86tn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qos0h86tn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:file-plus-filled" {...props}></Icon>
