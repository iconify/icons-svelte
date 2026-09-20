<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iht6htblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iht6htblh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:heart-edit-filled" {...props}></Icon>
