<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/a/azr-0u.css';
import '../../css/l/li54_l.css';
import '../../css/s/so-from-64.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c azr-0u"/><path class="a0m25c li54_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:briefcase" {...props}></Icon>
