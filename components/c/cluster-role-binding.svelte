<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kc8h-9bvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kc8h-9bvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:cluster-role-binding" {...props}></Icon>
