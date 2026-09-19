<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o563r6b9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o563r6b9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:magnifying-glass-plus-solid" {...props}></Icon>
