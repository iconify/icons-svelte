<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2o79t15y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f2o79t15y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:database-off" {...props}></Icon>
