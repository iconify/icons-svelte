<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqy-zd.css';
import '../../css/o/osh3oc.css';
import '../../css/s/so-from-60.css';
import '../../css/f/fade-to-1.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqy-zd"/><path class="osh3oc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:pixelfed" {...props}></Icon>
