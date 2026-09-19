<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1wf6ob-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o1wf6ob-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:pin" {...props}></Icon>
