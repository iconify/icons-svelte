<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djfh05m5o.css';
import '../../css/o/o6ao99dhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="djfh05m5o"/><path class="o6ao99dhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:ethereum" {...props}></Icon>
