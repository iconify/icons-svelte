<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brm-ghxcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="brm-ghxcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:crab" {...props}></Icon>
