<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9wv786kf.css';
import '../../css/j/jr0li4tsj.css';
import '../../css/x/x9t4ydb-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o9wv786kf"/><path class="jr0li4tsj"/><path class="x9t4ydb-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:blueprint-48" {...props}></Icon>
