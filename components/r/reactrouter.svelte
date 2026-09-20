<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8n95bc8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m8n95bc8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:reactrouter" {...props}></Icon>
