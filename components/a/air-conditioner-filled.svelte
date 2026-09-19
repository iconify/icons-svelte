<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojk8-p4ac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ojk8-p4ac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:air-conditioner-filled" {...props}></Icon>
