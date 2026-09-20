<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfvfo9eco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qfvfo9eco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:medicine" {...props}></Icon>
