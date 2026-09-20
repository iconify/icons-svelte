<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iku5nns_x.css';
import '../../css/i/ibhuv3bvf.css';
import '../../css/s/s1m0m1bfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iku5nns_x"/><path class="ibhuv3bvf"/><path class="s1m0m1bfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:entertainment-events-hobbies-record-player" {...props}></Icon>
