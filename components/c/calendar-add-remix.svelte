<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrd1i7udq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qrd1i7udq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:calendar-add-remix" {...props}></Icon>
