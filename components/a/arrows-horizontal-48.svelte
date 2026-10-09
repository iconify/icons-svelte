<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmb21zcef.css';
import '../../css/a/aw0qt-2do.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gmb21zcef"/><path class="aw0qt-2do"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrows-horizontal-48" {...props}></Icon>
