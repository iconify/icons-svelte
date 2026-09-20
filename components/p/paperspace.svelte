<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmiuys6ib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bmiuys6ib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:paperspace" {...props}></Icon>
