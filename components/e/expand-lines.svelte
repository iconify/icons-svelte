<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjmizab8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qjmizab8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:expand-lines" {...props}></Icon>
