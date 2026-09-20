<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkger6gry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lkger6gry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-65-small" {...props}></Icon>
