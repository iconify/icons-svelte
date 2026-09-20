<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz_8thepw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sz_8thepw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:receipt-filled" {...props}></Icon>
