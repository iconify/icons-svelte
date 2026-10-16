<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar3qoibyd.css';
import '../../css/r/rtsvhsn1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ar3qoibyd"/><path class="rtsvhsn1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hacksaw-48-bold" {...props}></Icon>
