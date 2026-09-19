<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eacdilb9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eacdilb9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:meeting-point" {...props}></Icon>
