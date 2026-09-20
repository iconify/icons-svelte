<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0o5wjnji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="h0o5wjnji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:align-left" {...props}></Icon>
