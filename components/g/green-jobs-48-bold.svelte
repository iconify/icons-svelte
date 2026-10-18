<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqidrqohi.css';
import '../../css/m/mq0070biz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="eqidrqohi"/><path class="mq0070biz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:green-jobs-48-bold" {...props}></Icon>
