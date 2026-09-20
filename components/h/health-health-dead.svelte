<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3285tnog.css';
import '../../css/r/rbbx4hzxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h3285tnog"/><path class="rbbx4hzxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:health-health-dead" {...props}></Icon>
