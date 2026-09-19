<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yplqs3nsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yplqs3nsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:no-access-for-service-animal-2" {...props}></Icon>
