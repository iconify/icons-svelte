<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg1m8dbxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jg1m8dbxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:error" {...props}></Icon>
