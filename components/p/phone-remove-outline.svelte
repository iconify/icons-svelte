<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrg1k343p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hrg1k343p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:phone-remove-outline" {...props}></Icon>
