<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqo-3m6rq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-2};
const content = `<path class="nqo-3m6rq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:glass-filled" {...props}></Icon>
