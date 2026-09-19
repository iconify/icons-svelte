<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqhqb842c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qqhqb842c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:config-ruby" {...props}></Icon>
