<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebs0_ubnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ebs0_ubnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:helicopter" {...props}></Icon>
