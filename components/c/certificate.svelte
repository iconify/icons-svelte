<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdcvev7wr.css';
import '../../css/f/fbeas_klm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdcvev7wr duoicon-primary-layer"/><path class="duoicon-secondary-layer fbeas_klm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:certificate" {...props}></Icon>
