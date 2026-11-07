<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9bla539y.css';
import '../../css/q/qbfdzwb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s9bla539y"/><path class="qbfdzwb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-down-to-line-outline" {...props}></Icon>
