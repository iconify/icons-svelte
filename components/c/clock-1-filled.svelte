<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_nb4-z7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_nb4-z7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:clock-1-filled" {...props}></Icon>
