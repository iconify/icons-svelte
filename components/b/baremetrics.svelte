<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie9q1cyqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ie9q1cyqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:baremetrics" {...props}></Icon>
