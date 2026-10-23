<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fter9dbfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fter9dbfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:playing-cards-fan" {...props}></Icon>
