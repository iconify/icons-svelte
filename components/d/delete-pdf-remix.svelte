<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwsl0ug_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gwsl0ug_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:delete-pdf-remix" {...props}></Icon>
