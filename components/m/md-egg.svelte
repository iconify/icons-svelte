<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilf5-qrkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ilf5-qrkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-egg" {...props}></Icon>
