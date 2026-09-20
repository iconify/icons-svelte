<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qn6gtwqvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qn6gtwqvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:motor" {...props}></Icon>
