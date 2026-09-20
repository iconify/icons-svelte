<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zk1bn3bmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zk1bn3bmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-navigation" {...props}></Icon>
