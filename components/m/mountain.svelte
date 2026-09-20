<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8et9mopb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x8et9mopb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:mountain" {...props}></Icon>
