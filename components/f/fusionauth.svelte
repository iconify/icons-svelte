<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y29-hdc1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y29-hdc1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:fusionauth" {...props}></Icon>
