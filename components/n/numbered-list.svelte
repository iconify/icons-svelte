<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azt6sbb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="azt6sbb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:numbered-list" {...props}></Icon>
