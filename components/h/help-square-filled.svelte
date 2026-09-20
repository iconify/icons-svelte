<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kq9xq1nkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kq9xq1nkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:help-square-filled" {...props}></Icon>
