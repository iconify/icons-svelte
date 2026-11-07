<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txb7wf95q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="txb7wf95q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bag-2-bold" {...props}></Icon>
