<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9fkq15nn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m9fkq15nn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:fitbit" {...props}></Icon>
