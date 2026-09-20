<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1xlz4bth.css';
import '../../css/o/ordys2bor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1xlz4bth"/><path class="ordys2bor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:bloomberg" {...props}></Icon>
