<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnfhb-bhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jnfhb-bhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:atom-solid" {...props}></Icon>
