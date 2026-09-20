<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b545u0bpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b545u0bpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:arrow-up-left" {...props}></Icon>
