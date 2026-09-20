<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agkwzcc7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="agkwzcc7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:json-duotone" {...props}></Icon>
