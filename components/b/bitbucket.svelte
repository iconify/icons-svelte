<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/of9xrlbih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1440,"height":1664};
const content = `<path class="of9xrlbih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:bitbucket" {...props}></Icon>
