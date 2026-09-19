<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_60j9k2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_60j9k2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:directions-02" {...props}></Icon>
