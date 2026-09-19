<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifq7fr6yy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ifq7fr6yy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:discord-filled" {...props}></Icon>
