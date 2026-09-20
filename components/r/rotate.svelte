<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/watb0jbco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="watb0jbco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:rotate" {...props}></Icon>
