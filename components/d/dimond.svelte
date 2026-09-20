<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzolh-kgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzolh-kgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:dimond" {...props}></Icon>
