<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkk5o7gkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bkk5o7gkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-letter-i" {...props}></Icon>
