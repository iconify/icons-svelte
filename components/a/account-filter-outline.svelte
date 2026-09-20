<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okfzjr1ec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="okfzjr1ec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-filter-outline" {...props}></Icon>
