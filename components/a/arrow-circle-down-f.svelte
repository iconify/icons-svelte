<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui5n0ibde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="ui5n0ibde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:arrow-circle-down-f" {...props}></Icon>
