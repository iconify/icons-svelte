<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilhchq55t.css';
import '../../css/c/cj4vqgbxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilhchq55t"/><path class="cj4vqgbxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bnb-line" {...props}></Icon>
