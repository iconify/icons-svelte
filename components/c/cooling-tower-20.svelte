<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8xms1bet.css';
import '../../css/w/wius6xb7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g8xms1bet"/><path class="wius6xb7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cooling-tower-20" {...props}></Icon>
