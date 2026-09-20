<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjeg9vz7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="wjeg9vz7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:arrow-circle-down-left" {...props}></Icon>
