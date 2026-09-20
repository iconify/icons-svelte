<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntolmmb6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ntolmmb6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:navigation-minus" {...props}></Icon>
