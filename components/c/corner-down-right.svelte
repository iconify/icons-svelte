<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7dm14bil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n7dm14bil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:corner-down-right" {...props}></Icon>
