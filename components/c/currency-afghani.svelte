<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bry0q2bum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bry0q2bum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:currency-afghani" {...props}></Icon>
