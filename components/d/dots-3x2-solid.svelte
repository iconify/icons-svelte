<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v24d5qvsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v24d5qvsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:dots-3x2-solid" {...props}></Icon>
