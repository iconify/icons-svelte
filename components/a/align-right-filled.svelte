<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghybnh57b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghybnh57b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:align-right-filled" {...props}></Icon>
