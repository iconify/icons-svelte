<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofhs3acob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ofhs3acob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:heart-broken-outline" {...props}></Icon>
