<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrk6y7b9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vrk6y7b9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:mug-solid" {...props}></Icon>
