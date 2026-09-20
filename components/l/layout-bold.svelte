<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-sk7cc9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t-sk7cc9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:layout-bold" {...props}></Icon>
