<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wg80ktboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wg80ktboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-sketch" {...props}></Icon>
