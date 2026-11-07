<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/coe7vibui.css';
import '../../css/u/ud8fztbcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="coe7vibui"/><path clip-rule="evenodd" class="ud8fztbcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bell-ring-outline" {...props}></Icon>
