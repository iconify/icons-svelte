<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itva-1bmg.css';
import '../../css/o/o6y24yasb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itva-1bmg"/><path class="o6y24yasb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:brush-sparkles-filled" {...props}></Icon>
