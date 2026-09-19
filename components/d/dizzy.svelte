<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwibdw4bb.css';
import '../../css/w/w0wj57jig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bwibdw4bb"/><path class="w0wj57jig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dizzy" {...props}></Icon>
