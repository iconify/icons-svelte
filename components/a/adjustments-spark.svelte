<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z22fae9xe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z22fae9xe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:adjustments-spark" {...props}></Icon>
