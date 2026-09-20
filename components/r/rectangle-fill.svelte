<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxcuk3bzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lxcuk3bzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:rectangle-fill" {...props}></Icon>
