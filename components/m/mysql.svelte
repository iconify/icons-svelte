<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjv0iobtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wjv0iobtt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:mysql" {...props}></Icon>
