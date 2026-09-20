<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nymrah1gn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-3,"top":-2.5};
const content = `<path class="nymrah1gn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:power" {...props}></Icon>
