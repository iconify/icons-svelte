<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/leul54bmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="leul54bmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:monitor-cellphone-favorite" {...props}></Icon>
