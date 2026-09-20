<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6rrf8d9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p6rrf8d9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:opium" {...props}></Icon>
