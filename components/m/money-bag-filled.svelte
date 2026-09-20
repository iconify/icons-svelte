<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qeijhkbof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qeijhkbof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:money-bag-filled" {...props}></Icon>
