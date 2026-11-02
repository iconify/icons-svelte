<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjbkop1ks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kjbkop1ks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hand-fill" {...props}></Icon>
