<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofvb_sb4h.css';
import '../../css/h/h-ft_9bvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ofvb_sb4h"/><path clip-rule="evenodd" class="h-ft_9bvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:laptop-phone" {...props}></Icon>
