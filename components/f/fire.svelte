<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1fb8tbny.css';
import '../../css/o/oyc5ru9aq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a1fb8tbny duoicon-primary-layer"/><path class="duoicon-secondary-layer oyc5ru9aq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:fire" {...props}></Icon>
