<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg8vf0byu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tg8vf0byu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:openapiinitiative" {...props}></Icon>
