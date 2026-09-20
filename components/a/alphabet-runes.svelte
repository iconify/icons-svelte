<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0m72u3lk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x0m72u3lk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:alphabet-runes" {...props}></Icon>
