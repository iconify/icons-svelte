<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ls6rt8bmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="ls6rt8bmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:brailleh" {...props}></Icon>
