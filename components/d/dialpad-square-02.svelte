<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyy9geb-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dyy9geb-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:dialpad-square-02" {...props}></Icon>
