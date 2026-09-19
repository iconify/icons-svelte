<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o20vhit8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o20vhit8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:file-minus-filled" {...props}></Icon>
