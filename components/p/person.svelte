<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x97qw9bgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x97qw9bgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:person" {...props}></Icon>
