<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-pn7fboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h-pn7fboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-expand-diagonal-02" {...props}></Icon>
