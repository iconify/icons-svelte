<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k55sakbtr.css';
import '../../css/i/ibrld782c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k55sakbtr"/><path class="ibrld782c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:apple-alt" {...props}></Icon>
