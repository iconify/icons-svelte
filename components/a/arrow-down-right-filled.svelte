<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a36ekem9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a36ekem9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-down-right-filled" {...props}></Icon>
