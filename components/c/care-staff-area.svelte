<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae6uv7dgk.css';
import '../../css/b/bkulhccha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ae6uv7dgk"/><path class="bkulhccha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:care-staff-area" {...props}></Icon>
