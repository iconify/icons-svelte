<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/moji97b3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="moji97b3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pencil-minus" {...props}></Icon>
