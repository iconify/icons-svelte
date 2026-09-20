<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oql-g90za.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oql-g90za"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:horn-fill" {...props}></Icon>
