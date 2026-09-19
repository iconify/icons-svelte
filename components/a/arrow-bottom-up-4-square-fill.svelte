<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxb7krdgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rxb7krdgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-bottom-up-4-square-fill" {...props}></Icon>
