<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2slfnbqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n2slfnbqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:pump" {...props}></Icon>
