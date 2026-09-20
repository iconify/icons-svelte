<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lo00hmxit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lo00hmxit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:credit-card" {...props}></Icon>
