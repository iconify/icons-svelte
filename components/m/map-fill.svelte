<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8fcnxmjq.css';
import '../../css/c/cdkh7bjct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h8fcnxmjq"/><circle class="cdkh7bjct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:map-fill" {...props}></Icon>
