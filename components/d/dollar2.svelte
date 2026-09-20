<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duprv2fpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="duprv2fpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:dollar2" {...props}></Icon>
