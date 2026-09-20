<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c44pee.css';
import '../../css/s/so-from-28.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c44pee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:link" {...props}></Icon>
