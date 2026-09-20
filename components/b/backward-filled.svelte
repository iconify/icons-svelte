<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ye9ypdw-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ye9ypdw-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:backward-filled" {...props}></Icon>
