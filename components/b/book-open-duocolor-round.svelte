<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcujul4wt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lcujul4wt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:book-open-duocolor-round" {...props}></Icon>
