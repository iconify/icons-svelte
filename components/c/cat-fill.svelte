<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvn8rskjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mvn8rskjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cat-fill" {...props}></Icon>
