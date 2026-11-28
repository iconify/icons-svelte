<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yydu7fitl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary yydu7fitl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:paintbrush-duotone" {...props}></Icon>
