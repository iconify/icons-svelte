<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwvbtus1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwvbtus1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:alarm-add-fill" {...props}></Icon>
