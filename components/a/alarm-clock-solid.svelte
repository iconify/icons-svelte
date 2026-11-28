<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6oxribxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6oxribxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:alarm-clock-solid" {...props}></Icon>
