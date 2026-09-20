<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0o05e1wo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t0o05e1wo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:play" {...props}></Icon>
