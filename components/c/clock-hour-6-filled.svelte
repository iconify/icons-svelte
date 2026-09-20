<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9cqabcqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9cqabcqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:clock-hour-6-filled" {...props}></Icon>
