<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6azs0btd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-6,"top":-2};
const content = `<path class="g6azs0btd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:arrows-v" {...props}></Icon>
