<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn7sslbdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-9};
const content = `<path class="hn7sslbdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:more-horizontal" {...props}></Icon>
