<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ge24s0bhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ge24s0bhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:kalm" {...props}></Icon>
