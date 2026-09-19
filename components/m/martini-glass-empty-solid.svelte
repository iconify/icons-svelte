<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdk6vevrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdk6vevrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:martini-glass-empty-solid" {...props}></Icon>
