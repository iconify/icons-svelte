<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq0tezbxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pq0tezbxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:notification-add-filled" {...props}></Icon>
