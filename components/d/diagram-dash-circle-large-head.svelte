<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovp4tye2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovp4tye2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:diagram-dash-circle-large-head" {...props}></Icon>
