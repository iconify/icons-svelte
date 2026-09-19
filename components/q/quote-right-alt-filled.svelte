<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0tt1ib_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v0tt1ib_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:quote-right-alt-filled" {...props}></Icon>
