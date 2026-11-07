<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgcuu1b3j.css';
import '../../css/q/qi9kc7bbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hgcuu1b3j"/><path clip-rule="evenodd" class="qi9kc7bbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:logout-2-bold-duotone" {...props}></Icon>
