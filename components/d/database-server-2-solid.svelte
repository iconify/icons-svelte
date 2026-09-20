<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abpo0gboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="abpo0gboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:database-server-2-solid" {...props}></Icon>
