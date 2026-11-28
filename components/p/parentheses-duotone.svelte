<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7fqenvds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary u7fqenvds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:parentheses-duotone" {...props}></Icon>
