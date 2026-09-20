<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6ldt11qt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x6ldt11qt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:layout-grid-2-fill" {...props}></Icon>
