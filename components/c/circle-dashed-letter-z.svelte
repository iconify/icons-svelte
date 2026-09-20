<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ust7zubzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ust7zubzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-dashed-letter-z" {...props}></Icon>
