<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqpw6snrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zqpw6snrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:line" {...props}></Icon>
