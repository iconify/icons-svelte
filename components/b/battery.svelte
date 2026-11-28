<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mi0dj3bmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mi0dj3bmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:battery" {...props}></Icon>
