<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o40c9wbap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o40c9wbap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:headphone-outline" {...props}></Icon>
