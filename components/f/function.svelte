<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyij-mfno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vyij-mfno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:function" {...props}></Icon>
