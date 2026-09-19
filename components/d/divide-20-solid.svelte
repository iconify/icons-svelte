<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb3iguelw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nb3iguelw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:divide-20-solid" {...props}></Icon>
