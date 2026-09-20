<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh3ha2b9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eh3ha2b9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:arrow-up-right" {...props}></Icon>
