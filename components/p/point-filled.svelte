<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo7ac-bbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qo7ac-bbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:point-filled" {...props}></Icon>
