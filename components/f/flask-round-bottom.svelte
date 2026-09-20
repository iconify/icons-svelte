<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/br14ndb4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="br14ndb4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flask-round-bottom" {...props}></Icon>
