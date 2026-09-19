<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3l4fgb5a.css';
import '../../css/k/k8xg7x5nk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j3l4fgb5a"/><path class="k8xg7x5nk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:buildings-filled" {...props}></Icon>
