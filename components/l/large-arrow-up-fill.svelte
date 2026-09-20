<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbhnk0kri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tbhnk0kri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:large-arrow-up-fill" {...props}></Icon>
