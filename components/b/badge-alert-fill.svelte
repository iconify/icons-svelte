<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av1mmm5yj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="av1mmm5yj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:badge-alert-fill" {...props}></Icon>
