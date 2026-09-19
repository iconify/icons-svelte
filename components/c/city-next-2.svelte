<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq2xzablw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="mq2xzablw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:city-next-2" {...props}></Icon>
