<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oegrs6bql.css';
import '../../css/o/o7hd-nb0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oegrs6bql"/><path class="o7hd-nb0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electricity-bill-48" {...props}></Icon>
