<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oh0km5biw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="oh0km5biw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:cloud-filled" {...props}></Icon>
