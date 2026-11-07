<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0-gkacxy.css';
import '../../css/y/yxn4dklvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s0-gkacxy"/><path class="yxn4dklvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folders-bold" {...props}></Icon>
