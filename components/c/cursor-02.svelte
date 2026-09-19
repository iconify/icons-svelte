<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zta7qc5xb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zta7qc5xb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cursor-02" {...props}></Icon>
