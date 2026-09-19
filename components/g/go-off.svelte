<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebn5a7bks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ebn5a7bks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:go-off" {...props}></Icon>
