<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_1qspb2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_1qspb2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-up-right-down-left-solid" {...props}></Icon>
