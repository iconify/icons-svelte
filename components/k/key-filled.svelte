<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2ijybc0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a2ijybc0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:key-filled" {...props}></Icon>
