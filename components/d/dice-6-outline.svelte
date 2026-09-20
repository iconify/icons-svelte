<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj3jorbai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oj3jorbai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:dice-6-outline" {...props}></Icon>
