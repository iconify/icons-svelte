<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oytpm0ile.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oytpm0ile"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bounce-left-filled" {...props}></Icon>
