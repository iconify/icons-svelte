<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uka2zbbdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uka2zbbdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flask-empty-minus-outline" {...props}></Icon>
