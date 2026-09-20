<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk1ad80py.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sk1ad80py"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:pluscodes" {...props}></Icon>
