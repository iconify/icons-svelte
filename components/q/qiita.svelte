<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njbyc1zgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="njbyc1zgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:qiita" {...props}></Icon>
