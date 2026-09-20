<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe63_5bkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fe63_5bkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:alarm-minus" {...props}></Icon>
