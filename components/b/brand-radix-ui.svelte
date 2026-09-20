<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcbq-w_3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jcbq-w_3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-radix-ui" {...props}></Icon>
