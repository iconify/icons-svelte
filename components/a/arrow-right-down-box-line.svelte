<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8k1dqb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j8k1dqb5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-right-down-box-line" {...props}></Icon>
