<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ao2q88qfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ao2q88qfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:monitor-favorite" {...props}></Icon>
