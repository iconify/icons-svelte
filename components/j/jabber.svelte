<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v43-w8bka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":667.188,"height":1000};
const content = `<path class="v43-w8bka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="brandico:jabber" {...props}></Icon>
