<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy6c65bfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sy6c65bfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:building-complex" {...props}></Icon>
