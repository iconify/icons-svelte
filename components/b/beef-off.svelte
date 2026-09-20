<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofpns1bla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ofpns1bla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:beef-off" {...props}></Icon>
