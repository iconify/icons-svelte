<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0jzetbxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t0jzetbxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:inbox-archive-bold" {...props}></Icon>
