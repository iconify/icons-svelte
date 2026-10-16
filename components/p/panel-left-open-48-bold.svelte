<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9a09orqa.css';
import '../../css/x/xklhocbaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="q9a09orqa"/><path class="xklhocbaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:panel-left-open-48-bold" {...props}></Icon>
