<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx0rgvnfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sx0rgvnfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hashtag-line" {...props}></Icon>
