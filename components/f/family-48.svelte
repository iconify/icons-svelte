<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ky87bk4jd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ky87bk4jd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:family-48" {...props}></Icon>
