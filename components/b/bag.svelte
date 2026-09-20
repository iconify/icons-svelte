<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au-v0i33b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="au-v0i33b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:bag" {...props}></Icon>
