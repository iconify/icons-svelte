<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb0ntgzah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lb0ntgzah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:api-app" {...props}></Icon>
