<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r61hukbbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r61hukbbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:nightstand-filled" {...props}></Icon>
