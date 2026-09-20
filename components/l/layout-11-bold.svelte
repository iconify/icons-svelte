<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbem5n73m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lbem5n73m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:layout-11-bold" {...props}></Icon>
