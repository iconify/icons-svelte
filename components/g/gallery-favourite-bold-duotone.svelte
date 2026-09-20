<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avbyq5urn.css';
import '../../css/r/r9qd5__9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avbyq5urn"/><path clip-rule="evenodd" class="r9qd5__9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gallery-favourite-bold-duotone" {...props}></Icon>
