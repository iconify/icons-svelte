<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr9mfq_-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kr9mfq_-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:battery-low-fill" {...props}></Icon>
