<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0uqmxbcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h0uqmxbcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:circle-arrows-down" {...props}></Icon>
