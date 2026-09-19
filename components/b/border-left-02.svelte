<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umn82f6mz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="umn82f6mz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:border-left-02" {...props}></Icon>
