<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1xymydmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1xymydmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:briefcase" {...props}></Icon>
