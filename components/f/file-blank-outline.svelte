<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/allq33zyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="allq33zyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:file-blank-outline" {...props}></Icon>
