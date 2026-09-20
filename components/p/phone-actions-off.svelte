<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukjdqe4vc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ukjdqe4vc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:phone-actions-off" {...props}></Icon>
