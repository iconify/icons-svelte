<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bet2wtq1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bet2wtq1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-up-1-fill" {...props}></Icon>
