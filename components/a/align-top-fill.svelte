<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3vfqt30y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a3vfqt30y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-top-fill" {...props}></Icon>
