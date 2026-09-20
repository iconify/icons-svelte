<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc9k5vb_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jc9k5vb_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:caravan-fill" {...props}></Icon>
