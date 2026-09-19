<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzaeyspsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzaeyspsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:remove-circle-half-dot" {...props}></Icon>
